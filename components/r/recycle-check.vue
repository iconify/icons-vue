<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmw3_6bzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmw3_6bzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:recycle-check" /></template>
