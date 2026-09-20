<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy980mv1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sy980mv1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:volume-off" /></template>
