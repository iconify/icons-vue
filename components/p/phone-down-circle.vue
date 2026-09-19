<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_0ic6bna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="f_0ic6bna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:phone-down-circle" /></template>
