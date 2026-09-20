<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8q6hq01f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8q6hq01f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:textalign-justifyright-filled" /></template>
