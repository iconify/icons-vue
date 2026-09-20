<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yle_3hkkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yle_3hkkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:xbox-game-pass-light" /></template>
