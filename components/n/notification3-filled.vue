<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls470t6zi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ls470t6zi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:notification3-filled" /></template>
