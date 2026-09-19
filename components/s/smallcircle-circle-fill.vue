<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5nh14bgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="q5nh14bgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:smallcircle-circle-fill" /></template>
