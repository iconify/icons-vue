<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc9lglftr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yc9lglftr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:square-sort-h" /></template>
