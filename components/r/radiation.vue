<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7w0gcror.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7w0gcror"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:radiation" /></template>
