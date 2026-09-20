<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fht-kwr4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fht-kwr4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:polaroid" /></template>
