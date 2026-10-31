<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c85pd_b_f.css';
import '../../css/p/p8ch74sqh.css';
import '../../css/n/nlhkcl_uv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="c85pd_b_f"/><path class="p8ch74sqh"/><path class="nlhkcl_uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:marshall-islands" /></template>
