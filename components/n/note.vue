<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l17nmcc_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l17nmcc_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:note" /></template>
