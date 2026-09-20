<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvgr61b0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="zvgr61b0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:phone" /></template>
