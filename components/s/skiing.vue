<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nm4c8-w_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nm4c8-w_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:skiing" /></template>
