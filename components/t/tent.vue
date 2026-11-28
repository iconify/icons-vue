<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye2rk2b4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye2rk2b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:tent" /></template>
