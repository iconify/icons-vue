<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_t-t1bub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_t-t1bub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:shutdown" /></template>
