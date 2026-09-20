<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj-4iwbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yj-4iwbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:socket-io" /></template>
