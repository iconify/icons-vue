<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/w/wzu4c0bsi.css';
import '../../css/z/zf_z6v05p.css';
import '../../css/n/nqvv9lbxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="wzu4c0bsi"/><circle class="zf_z6v05p"/><path class="nqvv9lbxu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:music-02" /></template>
