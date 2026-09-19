<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkj7g0bec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xkj7g0bec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:slack-stroke-12" /></template>
