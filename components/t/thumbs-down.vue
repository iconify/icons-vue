<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxs5r9b4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jxs5r9b4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:thumbs-down" /></template>
