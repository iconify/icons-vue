<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/faekp9bkh.css';
import '../../css/r/ry8otvb5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="faekp9bkh"/><path class="ry8otvb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:repoflow" /></template>
