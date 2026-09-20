<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al7berbgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="al7berbgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pingvin-share-x-light" /></template>
