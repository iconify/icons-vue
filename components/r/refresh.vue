<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/za0lhs10d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="za0lhs10d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:refresh" /></template>
