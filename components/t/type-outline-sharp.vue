<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsf_qtbke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsf_qtbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:type-outline-sharp" /></template>
