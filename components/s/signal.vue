<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au6ph-b7y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="au6ph-b7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:signal" /></template>
