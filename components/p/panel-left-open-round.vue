<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj1ixbbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj1ixbbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:panel-left-open-round" /></template>
