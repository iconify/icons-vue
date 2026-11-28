<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he_ewtb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="he_ewtb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tally-3-solid" /></template>
