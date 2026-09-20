<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7yeswbyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s7yeswbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:paragraph-solid" /></template>
