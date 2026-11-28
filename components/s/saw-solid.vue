<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry5_eaccq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ry5_eaccq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:saw-solid" /></template>
