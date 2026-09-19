<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g27e14bba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="g27e14bba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:wheat-awn-circle-exclamation" /></template>
