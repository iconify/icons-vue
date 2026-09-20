<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo5-5tayx.css';
import '../../css/a/ars70-b2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vo5-5tayx"/><path clip-rule="evenodd" class="ars70-b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:other-ui-award" /></template>
