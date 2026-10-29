<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axaf_tbrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axaf_tbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wifi-low-solid" /></template>
