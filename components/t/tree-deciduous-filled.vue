<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt_whcb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zt_whcb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tree-deciduous-filled" /></template>
