<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwn4_kbny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="lwn4_kbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:oil-can" /></template>
