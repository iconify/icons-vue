<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc7tgwran.css';
import '../../css/r/rv7f2sbom.css';
import '../../css/z/zk1j0x1lv.css';
import '../../css/m/m99nb8bny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nc7tgwran"/><path class="rv7f2sbom"/><path class="zk1j0x1lv"/><path class="m99nb8bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:memorystore" /></template>
