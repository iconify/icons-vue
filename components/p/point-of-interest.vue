<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrut08e3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrut08e3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:point-of-interest" /></template>
