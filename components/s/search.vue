<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1yh6f2dv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":766};
const content = `<path class="u1yh6f2dv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:search" /></template>
