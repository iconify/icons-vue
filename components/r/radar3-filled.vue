<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0a3z3bzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0a3z3bzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:radar3-filled" /></template>
