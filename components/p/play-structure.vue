<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq-fxh_-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jq-fxh_-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:play-structure" /></template>
