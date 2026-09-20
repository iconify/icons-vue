<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iigzff37x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iigzff37x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:topcoder" /></template>
