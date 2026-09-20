<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd2q-gb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="xd2q-gb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:scanner-3" /></template>
