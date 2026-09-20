<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fop6pbdfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fop6pbdfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:wordpress-simple" /></template>
