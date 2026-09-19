<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrbckyotk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":675,"height":717};
const content = `<path class="rrbckyotk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:memo" /></template>
