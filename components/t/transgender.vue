<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvithbb2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1792};
const content = `<path class="wvithbb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:transgender" /></template>
