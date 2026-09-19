<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on57_q5jc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="on57_q5jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:podcast" /></template>
