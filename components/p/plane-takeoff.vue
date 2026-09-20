<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkd-rr4pt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkd-rr4pt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:plane-takeoff" /></template>
