<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7qfycnrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7qfycnrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-chevron-left-fill" /></template>
