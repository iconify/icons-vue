<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9n_1vyxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u9n_1vyxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:server" /></template>
