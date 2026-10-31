<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs59oehdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zs59oehdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:screwdriver-fill-round" /></template>
