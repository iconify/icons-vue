<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbvxt794a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kbvxt794a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openleaf" /></template>
