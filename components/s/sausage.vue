<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4jvhibng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4jvhibng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sausage" /></template>
