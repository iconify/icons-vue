<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm20wygxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm20wygxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:suse" /></template>
