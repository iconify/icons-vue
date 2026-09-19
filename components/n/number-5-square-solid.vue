<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quyp2zbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="quyp2zbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:number-5-square-solid" /></template>
