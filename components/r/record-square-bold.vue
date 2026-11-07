<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_csnkffw.css';
import '../../css/k/kvt6enbri.css';
import '../../css/q/qwhmxvbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_csnkffw"/><path class="kvt6enbri"/><path clip-rule="evenodd" class="qwhmxvbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:record-square-bold" /></template>
