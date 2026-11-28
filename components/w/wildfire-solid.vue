<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkgykkh-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkgykkh-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:wildfire-solid" /></template>
