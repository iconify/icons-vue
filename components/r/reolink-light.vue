<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgl8q109f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kgl8q109f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:reolink-light" /></template>
