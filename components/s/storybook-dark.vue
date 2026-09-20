<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egkkoob5g.css';
import '../../css/o/ogb19tc_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="egkkoob5g"/><path class="ogb19tc_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:storybook-dark" /></template>
