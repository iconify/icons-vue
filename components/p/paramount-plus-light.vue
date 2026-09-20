<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shojepb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="shojepb7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:paramount-plus-light" /></template>
