<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-xy7fdst.css';
import '../../css/h/hcnon4f5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a-xy7fdst"/><path class="hcnon4f5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:swash" /></template>
