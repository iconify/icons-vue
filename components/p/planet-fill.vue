<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lycqc1r5r.css';
import '../../css/z/zphee1bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lycqc1r5r"/><path class="zphee1bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:planet-fill" /></template>
