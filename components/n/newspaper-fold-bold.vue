<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p22nvzbrb.css';
import '../../css/b/b2249gzmx.css';
import '../../css/g/giwlvbxak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p22nvzbrb"/><path class="b2249gzmx"/><path class="giwlvbxak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:newspaper-fold-bold" /></template>
