<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2crgeb7t.css';
import '../../css/q/qwqwk1bts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="w2crgeb7t"/><path clip-rule="evenodd" class="qwqwk1bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nextcloudpi-dark" /></template>
