<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck8bl2blq.css';
import '../../css/o/oiuivp-xw.css';
import '../../css/b/brgi00b6i.css';
import '../../css/p/p3d0wwbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck8bl2blq"/><path class="oiuivp-xw"/><path class="brgi00b6i"/><path class="p3d0wwbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:und" /></template>
