<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3ht_0i4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="s3ht_0i4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:send-backward-fill" /></template>
