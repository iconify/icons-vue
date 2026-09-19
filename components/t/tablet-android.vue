<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3ed8os0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="p3ed8os0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:tablet-android" /></template>
