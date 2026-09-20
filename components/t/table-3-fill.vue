<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp-3j-blm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gp-3j-blm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:table-3-fill" /></template>
