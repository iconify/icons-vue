<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow83bgbqz.css';
import '../../css/o/oexci5_ie.css';
import '../../css/w/wahgcobfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ow83bgbqz"/><path class="oexci5_ie"/><path class="wahgcobfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-help-circle-outline" /></template>
