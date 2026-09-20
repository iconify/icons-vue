<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0py9l3oo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r0py9l3oo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:umbrella-beach-solid" /></template>
