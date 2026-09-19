<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxib_rb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxib_rb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:trending-down" /></template>
