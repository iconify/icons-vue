<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb9rh5boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="bb9rh5boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:operate-plant-filled" /></template>
