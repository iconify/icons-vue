<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9khtibqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x9khtibqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:message-square-dashed-check-solid" /></template>
