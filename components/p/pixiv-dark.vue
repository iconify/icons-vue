<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f69_d7b-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f69_d7b-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pixiv-dark" /></template>
