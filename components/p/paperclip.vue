<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_dpj_7ql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_dpj_7ql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:paperclip" /></template>
