<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpuo92byx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpuo92byx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:person-standing-solid" /></template>
