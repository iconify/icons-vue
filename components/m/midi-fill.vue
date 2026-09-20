<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nx3_iti8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nx3_iti8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:midi-fill" /></template>
