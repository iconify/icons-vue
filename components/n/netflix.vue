<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qiqu0vbdz.css';
import '../../css/s/sjfxabblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qiqu0vbdz"/><path class="sjfxabblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:netflix" /></template>
