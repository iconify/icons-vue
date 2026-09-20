<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qea01pbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qea01pbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:restart-filled" /></template>
