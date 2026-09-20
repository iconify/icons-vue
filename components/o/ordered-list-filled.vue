<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0enz769b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0enz769b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ordered-list-filled" /></template>
