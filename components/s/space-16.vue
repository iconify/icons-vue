<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8dgv7ect.css';
import '../../css/c/c4hlqdbyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n8dgv7ect"/><path class="c4hlqdbyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:space-16" /></template>
