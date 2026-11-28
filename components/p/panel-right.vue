<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0dw7vbzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0dw7vbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:panel-right" /></template>
