<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c625vx81f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="c625vx81f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:speedometer" /></template>
