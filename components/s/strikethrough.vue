<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bw8c2qbhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bw8c2qbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:strikethrough" /></template>
