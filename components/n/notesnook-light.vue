<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-_vu6g8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y-_vu6g8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:notesnook-light" /></template>
