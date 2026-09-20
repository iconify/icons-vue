<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl_gb3b1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vl_gb3b1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:user-shield-solid" /></template>
