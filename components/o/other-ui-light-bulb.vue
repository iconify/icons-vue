<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvswe7bnc.css';
import '../../css/o/of3lo06ag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fvswe7bnc"/><path class="of3lo06ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:other-ui-light-bulb" /></template>
