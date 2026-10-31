<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po1nvfbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="po1nvfbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:navigation-alt-duocolor-round" /></template>
