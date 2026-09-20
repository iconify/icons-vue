<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omdqejbnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omdqejbnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:t-shirt-2-fill" /></template>
