<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-pg_gpqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z-pg_gpqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:portrait-solid" /></template>
