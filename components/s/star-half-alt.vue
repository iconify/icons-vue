<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vpbdes8bw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpbdes8bw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:star-half-alt" /></template>
