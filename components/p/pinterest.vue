<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc6mpdb9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4.5,"top":-2};
const content = `<path class="xc6mpdb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:pinterest" /></template>
