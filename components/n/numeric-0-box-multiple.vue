<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3ctc8bln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3ctc8bln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-0-box-multiple" /></template>
