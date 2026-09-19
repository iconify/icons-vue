<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkb_vzbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkb_vzbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:wall" /></template>
