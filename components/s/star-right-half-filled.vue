<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcst-z.css';
import '../../css/n/n5xegl.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-from-34.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcst-z"/><path class="n5xegl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:star-right-half-filled" /></template>
