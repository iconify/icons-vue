<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1maur2rn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x1maur2rn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:percent-square-filled" /></template>
