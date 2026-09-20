<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt-9dzk5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt-9dzk5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:powerpoint" /></template>
