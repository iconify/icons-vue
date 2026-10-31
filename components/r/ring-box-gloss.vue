<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi1hhvbbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xi1hhvbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ring-box-gloss" /></template>
