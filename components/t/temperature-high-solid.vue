<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erakx_b9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="erakx_b9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:temperature-high-solid" /></template>
