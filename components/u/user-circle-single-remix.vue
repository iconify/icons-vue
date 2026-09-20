<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy-flpdnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sy-flpdnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:user-circle-single-remix" /></template>
