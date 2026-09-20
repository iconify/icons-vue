<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1yk08bdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1yk08bdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:xda" /></template>
