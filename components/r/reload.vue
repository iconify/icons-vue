<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjyda_60k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjyda_60k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:reload" /></template>
