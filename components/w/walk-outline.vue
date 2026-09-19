<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw1hwcn4c.css';
import '../../css/u/u7peyabnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zw1hwcn4c"/><circle class="u7peyabnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:walk-outline" /></template>
