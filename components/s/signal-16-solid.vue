<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mim6rebae.css';
import '../../css/t/tfnvfpbmm.css';
import '../../css/a/at4prjc-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mim6rebae"/><path clip-rule="evenodd" class="tfnvfpbmm"/><path clip-rule="evenodd" class="at4prjc-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:signal-16-solid" /></template>
