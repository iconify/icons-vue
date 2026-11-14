<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/bt4xg4ftq.css';
import '../../css/f/fhas8sg6b.css';
import '../../css/r/rbw7kknaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bt4xg4ftq"/><path class="fhas8sg6b"/><path class="rbw7kknaz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wallet-done-01" /></template>
