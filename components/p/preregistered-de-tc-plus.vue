<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3ibv6b2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f3ibv6b2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:preregistered-de-tc-plus" /></template>
