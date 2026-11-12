<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxvxe8b2t.css';
import '../../css/q/qybors25i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gxvxe8b2t"/><path class="qybors25i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:toodoom-light" /></template>
