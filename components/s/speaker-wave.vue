<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnoshbbzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnoshbbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:speaker-wave" /></template>
