<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zew7-c2gj.css';
import '../../css/v/vea0ry4ig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zew7-c2gj"/><path class="vea0ry4ig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextbeats" /></template>
