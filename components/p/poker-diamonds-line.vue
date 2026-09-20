<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsf_iqb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsf_iqb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:poker-diamonds-line" /></template>
