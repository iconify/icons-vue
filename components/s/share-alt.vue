<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwc9hobsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="qwc9hobsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:share-alt" /></template>
