<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce_6m1h3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ce_6m1h3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:stumbleupon" /></template>
