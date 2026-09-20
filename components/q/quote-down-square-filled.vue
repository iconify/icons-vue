<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz2aoacna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cz2aoacna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:quote-down-square-filled" /></template>
