<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9pw-hbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u9pw-hbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:two-two" /></template>
