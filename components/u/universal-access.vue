<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdssnbbom.css';
import '../../css/b/bwibdw4bb.css';
import '../../css/q/q285h9bpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdssnbbom"/><path class="bwibdw4bb"/><path class="q285h9bpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:universal-access" /></template>
