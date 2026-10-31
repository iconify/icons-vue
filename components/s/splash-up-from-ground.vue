<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb-a68b2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fb-a68b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:splash-up-from-ground" /></template>
