<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg1_tcypd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qg1_tcypd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:tool" /></template>
