<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wolgdubtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wolgdubtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:misskey-light" /></template>
