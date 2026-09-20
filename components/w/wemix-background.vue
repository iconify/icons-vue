<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="pb9qmwxwx"/><path clip-rule="evenodd" class="xmf5zbbky"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wemix-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.pb9qmwxwx {
  fill: var(--svg-color--27ea84, #27ea84);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.xmf5zbbky {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M20 12a8 8 0 0 1-15.748 2H5.29A7 7 0 0 0 19 12h-.798l-1.076 1.372a.418.418 0 0 1-.764-.107l-.665-2.514l-.706 3.49c-.093.458-.75.444-.823-.016l-.656-4.115l-.9 6.657a.41.41 0 0 1-.813-.11l1.265-9.365c.065-.478.752-.486.829-.01l.734 4.615l.607-3c.088-.434.702-.452.815-.024l.861 3.256l.703-.946c.076-.127.213-.183.36-.183h1.965q.062.492.062 1m-.252-2a8 8 0 0 0-15.686 3h2.091a.43.43 0 0 0 .366-.232l.505-.737l.912 2.944c.128.41.717.385.81-.035l.631-2.879l.732 4.588c.076.478.768.467.829-.012l1.21-9.435a.41.41 0 1 0-.814-.105l-.855 6.662l-.626-3.926c-.072-.456-.723-.475-.822-.023l-.761 3.467l-.742-2.39a.419.419 0 0 0-.766-.079L5.915 12H5a7 7 0 0 1 13.71-2z");
}

</style>
