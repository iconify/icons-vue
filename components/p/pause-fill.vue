<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-hwwbb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-hwwbb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:pause-fill" /></template>
