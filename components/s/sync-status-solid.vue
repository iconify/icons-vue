<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/caxrc5bwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="caxrc5bwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:sync-status-solid" /></template>
