<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgjtln_kv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qgjtln_kv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:woozy-face-in-circle-outline" /></template>
