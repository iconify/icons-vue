<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbfwtcrgz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbfwtcrgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ppc" /></template>
