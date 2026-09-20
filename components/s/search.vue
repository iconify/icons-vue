<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isk5td_we.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isk5td_we"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:search" /></template>
