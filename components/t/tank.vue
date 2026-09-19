<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssb7-fbpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1026,"height":1024};
const content = `<path class="ssb7-fbpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:tank" /></template>
