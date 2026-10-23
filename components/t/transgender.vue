<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_vitv5oe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_vitv5oe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:transgender" /></template>
