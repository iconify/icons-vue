<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t55a15lpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t55a15lpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:washing-machine-clock" /></template>
