<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo753mubx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mo753mubx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:poop-solid" /></template>
