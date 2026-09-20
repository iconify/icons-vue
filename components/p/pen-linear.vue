<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/beni0rbag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="beni0rbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pen-linear" /></template>
