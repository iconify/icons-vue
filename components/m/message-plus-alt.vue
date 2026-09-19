<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtx1xb55s.css';
import '../../css/w/wfevvhiis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtx1xb55s"/><path class="wfevvhiis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:message-plus-alt" /></template>
