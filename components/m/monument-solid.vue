<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz75x3bje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rz75x3bje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:monument-solid" /></template>
