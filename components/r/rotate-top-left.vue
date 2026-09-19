<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo31weeay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oo31weeay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rotate-top-left" /></template>
