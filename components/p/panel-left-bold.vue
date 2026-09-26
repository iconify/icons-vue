<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn0qq-buc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qn0qq-buc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-left-bold" /></template>
