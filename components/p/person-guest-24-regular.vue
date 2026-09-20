<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhz4uwbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-guest-24-regular" /></template>
<style>
.dhz4uwbng {
  fill: currentColor;
  d: path("M20.5 12a2.5 2.5 0 0 1 2.5 2.5v6a2.5 2.5 0 0 1-2.5 2.5h-4a2.5 2.5 0 0 1-2.5-2.5v-6a2.5 2.5 0 0 1 2.5-2.5zm-7.464 2q-.035.245-.036.5v1H4.253a.75.75 0 0 0-.75.749v.578c.001.536.192 1.054.54 1.461c1.253 1.468 3.219 2.213 5.957 2.213q1.694-.002 3-.382v.381c0 .394.066.772.185 1.125Q11.752 22 10 22.001c-3.146 0-5.531-.905-7.098-2.74a3.75 3.75 0 0 1-.898-2.434v-.578A2.25 2.25 0 0 1 4.253 14zM17 14a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1zM10 2.005a5 5 0 1 1 0 10a5 5 0 0 1 0-10m0 1.5a3.5 3.5 0 1 0 0 7a3.5 3.5 0 0 0 0-7");
}

</style>
