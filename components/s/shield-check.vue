<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jngw48yvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2016,"height":2176};
const content = `<path class="jngw48yvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:shield-check" /></template>
