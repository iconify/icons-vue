<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyjird44w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyjird44w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:routing-filled" /></template>
