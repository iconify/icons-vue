<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyym7th_s.css';
import '../../css/q/qh35-indc.css';
import '../../css/g/gegqcfbxn.css';
import '../../css/s/s16aoqb6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lyym7th_s"/><path class="qh35-indc"/><path class="gegqcfbxn"/><path class="s16aoqb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:transfer-zip-dark" /></template>
