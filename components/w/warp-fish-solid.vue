<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5enqzbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x5enqzbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:warp-fish-solid" /></template>
