<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yje-c3cxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yje-c3cxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:panel-bottom-filled" /></template>
