<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai5_8yjej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":23,"height":24};
const content = `<path class="ai5_8yjej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:quora" /></template>
