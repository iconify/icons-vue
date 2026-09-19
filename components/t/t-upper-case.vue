<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iajkaacuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":455,"height":735};
const content = `<path class="iajkaacuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:t-upper-case" /></template>
