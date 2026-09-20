<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="vfqsn5p_y"/><path clip-rule="evenodd" class="iedyett1s"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xtp-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iedyett1s {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M8 4h8a4 4 0 0 1 4 4v8a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4V8a4 4 0 0 1 4-4m-1.81 7.84c0-3.965 3.24-5.66 5.755-5.66c4.385 0 5.93 3.425 5.93 5.83c0 1.198-.285 1.862-.407 2.148l-.018.041c-.09.216-.4.6-.83.38c-.345-.175-.285-.725-.125-1c.265-.45.29-1.21.265-1.57c0-3.55-3.165-4.754-4.815-4.754c-1.37 0-4.65.935-4.675 4.754c-.015 3.06 2.785 4.46 4.15 4.726c.28.02.78.15.72.58c-.055.43-.49.43-.72.43a5.87 5.87 0 0 1-5.23-5.906m2.145.03c0-2.126 1.955-3.6 3.795-3.51c2.73.125 3.5 2.37 3.5 3.62c0 .78-.235.88-.55.88c-.31 0-.4-.465-.4-.88a2.55 2.55 0 0 0-2.55-2.536c-.865 0-2.75.47-2.765 2.535c-.005 1.35.82 2.315 1.675 2.476c.235.05.465.3.4.565c-.07.27-.28.32-.535.32c-1.18-.06-2.57-1.34-2.57-3.47m4.175 2.75a4.15 4.15 0 0 0 1.575-.98c.105-.1.435-.176.675.125c.235.304.1.6 0 .714a5.9 5.9 0 0 1-1.765 1.166c-.185.09-.5-.02-.635-.285c-.14-.265-.075-.675.15-.74");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vfqsn5p_y {
  fill: var(--svg-color--3377f8, #3377f8);
  d: path("M24 0H0v24h24z");
}

</style>
