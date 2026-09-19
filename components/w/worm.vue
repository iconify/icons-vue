<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv9a28bxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kv9a28bxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:worm" /></template>
