<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmdp-p_5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="rmdp-p_5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-arrow-up-on-square-fill" /></template>
