<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blowczb_d.css';
import '../../css/e/e4jz-uehp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="blowczb_d"/><path class="e4jz-uehp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:other-ui-maximize" /></template>
