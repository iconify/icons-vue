<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v07et2bvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v07et2bvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:refresh" /></template>
