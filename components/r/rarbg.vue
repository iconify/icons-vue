<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7eewub9u.css';
import '../../css/x/x4yr5kbub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p7eewub9u"/><path class="x4yr5kbub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:rarbg" /></template>
