<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzi7zfbtp.css';
import '../../css/f/fh60u4boo.css';
import '../../css/c/cnio1-a_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tzi7zfbtp"/><path class="fh60u4boo"/><path class="cnio1-a_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:megaphone-16" /></template>
