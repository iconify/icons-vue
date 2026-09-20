<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqzs6hu8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-alert-off-24-regular" /></template>
<style>
.nqzs6hu8p {
  fill: currentColor;
  d: path("M19.002 22c-.218.582-.808 1-1.5 1s-1.282-.418-1.5-1zm-6.282-9.28a.75.75 0 0 1 1.06 0l8.5 8.5a.75.75 0 0 1-1.06 1.06L19.94 21h-6.948c-.402 0-.604 0-.705-.048a.5.5 0 0 1-.241-.661c.047-.101.2-.231.508-.49l.948-.801v-3a4 4 0 0 1 .197-1.24l-.98-.98a.75.75 0 0 1 0-1.06M11.67 14c.085.176.197.342.343.487l.577.578a5 5 0 0 0-.046.295l-.019.14H4.253a.75.75 0 0 0-.75.749v.577c0 .536.192 1.054.54 1.461c1.253 1.468 3.219 2.214 5.957 2.214q.518 0 .998-.035a1.5 1.5 0 0 0 .908 1.412Q11.006 22 10 22c-3.146 0-5.531-.905-7.098-2.74a3.75 3.75 0 0 1-.898-2.435v-.577A2.25 2.25 0 0 1 4.253 14zm5.832-2a4 4 0 0 1 4 4v2H21.5v1.025l-6.298-6.297a4 4 0 0 1 2.3-.728M10 2.005a5 5 0 1 1 0 10a5 5 0 0 1 0-10m0 1.5a3.5 3.5 0 1 0 0 7a3.5 3.5 0 0 0 0-7");
}

</style>
