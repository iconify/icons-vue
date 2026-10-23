<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-n617zmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-n617zmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:panel-right-dashed" /></template>
