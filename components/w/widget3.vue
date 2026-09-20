<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w17_hf4ys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w17_hf4ys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:widget3" /></template>
