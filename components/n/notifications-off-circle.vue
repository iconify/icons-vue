<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arsnl03rv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="arsnl03rv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:notifications-off-circle" /></template>
