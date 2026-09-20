<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4-w59gzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4-w59gzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:wind-electricity" /></template>
