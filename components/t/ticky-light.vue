<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-4uxpbxq.css';
import '../../css/r/rh7zq0bch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c-4uxpbxq"/><path class="rh7zq0bch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ticky-light" /></template>
