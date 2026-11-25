<script setup>
import { Head, Link } from '@inertiajs/vue3';
</script>

<template>
    <Head title="Contact Us" />
    <div class="min-h-screen bg-gray-100 flex flex-col items-center pt-16">
        <div class="w-full max-w-md bg-white p-6 rounded shadow">
            <h1 class="text-2xl font-bold mb-4">Contact Us</h1>
            <p>Email: info@example.com</p>
            <p>Phone: 0912 345 6789</p>
            <p>Address: Cebu City, Philippines</p>
            <Link href="/" class="text-blue-600 underline mt-4 inline-block">Back to Home</Link>
        </div>
    </div>
</template>