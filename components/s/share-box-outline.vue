<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkmq48bsn.css';
import '../../css/q/qd1ggccdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mkmq48bsn"/><path class="qd1ggccdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:share-box-outline" /></template>
