<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gemmb2bwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gemmb2bwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:table-2" /></template>
