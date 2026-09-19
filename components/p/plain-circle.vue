<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zszfq8dqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zszfq8dqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:plain-circle" /></template>
