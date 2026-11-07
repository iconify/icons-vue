<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gs3ov8moq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gs3ov8moq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:margin-top" /></template>
