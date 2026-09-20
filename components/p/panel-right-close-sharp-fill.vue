<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2_--acwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2_--acwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-right-close-sharp-fill" /></template>
