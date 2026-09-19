<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_dm8lvdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_dm8lvdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:top-window-open" /></template>
