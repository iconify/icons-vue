<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns9ftsbdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ns9ftsbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:trash4" /></template>
