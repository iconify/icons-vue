<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6pws_bay.css';
import '../../css/x/xj2ftdbyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c6pws_bay"/><path clip-rule="evenodd" class="xj2ftdbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:vector-document-solid" /></template>
