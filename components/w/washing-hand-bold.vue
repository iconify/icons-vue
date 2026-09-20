<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usw_opafh.css';
import '../../css/s/s9jcc4brv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usw_opafh"/><path class="s9jcc4brv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:washing-hand-bold" /></template>
