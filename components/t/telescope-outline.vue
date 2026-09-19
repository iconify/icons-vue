<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy3iztbmk.css';
import '../../css/s/sulj6_b9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oy3iztbmk"/><path class="sulj6_b9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:telescope-outline" /></template>
