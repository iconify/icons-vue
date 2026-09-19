<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfpabs99x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfpabs99x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:tennis" /></template>
