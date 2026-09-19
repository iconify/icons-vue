<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/bgk_arrkt.css';
import '../../css/f/fdtkzu5vr.css';
import '../../css/c/cf56gjb1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bgk_arrkt"/><path class="fdtkzu5vr"/><path class="cf56gjb1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:upload-03" /></template>
