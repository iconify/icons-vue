<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsi-fwbsz.css';
import '../../css/n/n90ye8oqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsi-fwbsz wm-k"/><path class="n90ye8oqo wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:superscript" /></template>
