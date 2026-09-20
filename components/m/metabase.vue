<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djn8p2b7h.css';
import '../../css/x/xefnkubua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="djn8p2b7h"/><path class="xefnkubua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:metabase" /></template>
