<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5z-5bcwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h5z-5bcwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:skip-filled" /></template>
