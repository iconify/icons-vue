<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5x5bmbqt.css';
import '../../css/a/axpn5ibac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z5x5bmbqt"/><path class="axpn5ibac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netgoat" /></template>
