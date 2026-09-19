<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj-7uouhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lj-7uouhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:sunrise-filled" /></template>
