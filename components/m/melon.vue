<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eho20050m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eho20050m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:melon" /></template>
