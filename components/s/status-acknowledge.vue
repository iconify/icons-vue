<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4n9_hbzl.css';
import '../../css/v/v1j9wac_l.css';
import '../../css/v/vbzy9bb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q4n9_hbzl"/><path class="v1j9wac_l"/><path class="vbzy9bb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:status-acknowledge" /></template>
