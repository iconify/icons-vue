<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt4cuabsh.css';
import '../../css/s/s3xv2_brc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bt4cuabsh"/><path clip-rule="evenodd" class="s3xv2_brc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:shuffle-outline" /></template>
