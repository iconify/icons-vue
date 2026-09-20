<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz7h7p0mm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oz7h7p0mm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:measurement-2-filled" /></template>
