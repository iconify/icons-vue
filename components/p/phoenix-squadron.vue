<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbo3mlqmu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lbo3mlqmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:phoenix-squadron" /></template>
