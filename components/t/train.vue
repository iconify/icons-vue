<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh2-3_b2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bh2-3_b2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:train" /></template>
