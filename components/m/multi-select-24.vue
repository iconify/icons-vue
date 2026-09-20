<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw1f1uo6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw1f1uo6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:multi-select-24" /></template>
