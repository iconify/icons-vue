<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_gh3fqas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_gh3fqas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:star-half-s-line" /></template>
