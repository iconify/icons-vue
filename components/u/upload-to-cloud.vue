<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp89m8b4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":448};
const content = `<path class="jp89m8b4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:upload-to-cloud" /></template>
