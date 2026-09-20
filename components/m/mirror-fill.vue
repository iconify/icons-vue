<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9o5c_wqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9o5c_wqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mirror-fill" /></template>
