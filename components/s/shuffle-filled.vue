<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqngrw5ya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wqngrw5ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:shuffle-filled" /></template>
