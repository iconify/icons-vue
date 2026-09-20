<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmy1g3b0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="kmy1g3b0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:terminal" /></template>
