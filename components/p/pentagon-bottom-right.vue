<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgu0890lw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bgu0890lw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:pentagon-bottom-right" /></template>
