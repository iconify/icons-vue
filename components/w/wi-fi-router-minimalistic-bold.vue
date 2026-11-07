<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cywuxumuo.css';
import '../../css/o/ov2kgdwro.css';
import '../../css/x/xpyf_2bdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cywuxumuo"/><path clip-rule="evenodd" class="ov2kgdwro"/><path class="xpyf_2bdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wi-fi-router-minimalistic-bold" /></template>
