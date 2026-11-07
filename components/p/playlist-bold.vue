<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc4jqtbfv.css';
import '../../css/n/nt_tpccog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pc4jqtbfv"/><path class="nt_tpccog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:playlist-bold" /></template>
