<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb53x88iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gb53x88iz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:textformat-wrap" /></template>
