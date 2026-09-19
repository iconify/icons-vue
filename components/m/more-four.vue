<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu3p7dkjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cu3p7dkjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:more-four" /></template>
