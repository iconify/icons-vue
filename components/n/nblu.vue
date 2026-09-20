<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccfj3dt4e.css';
import '../../css/g/gps6u6bmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccfj3dt4e"/><path class="gps6u6bmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:nblu" /></template>
