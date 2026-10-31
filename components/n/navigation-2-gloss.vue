<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xh4-wacdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xh4-wacdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:navigation-2-gloss" /></template>
