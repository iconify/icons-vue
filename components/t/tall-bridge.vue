<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl__lrbqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gl__lrbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tall-bridge" /></template>
