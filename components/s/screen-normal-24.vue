<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/errsw2beg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="errsw2beg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:screen-normal-24" /></template>
