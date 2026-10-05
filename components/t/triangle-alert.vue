<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/b/burtvrwyn.css';
import '../../css/g/g5e1kgbax.css';
import '../../css/a/a3uie0bxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="burtvrwyn"/><path class="g5e1kgbax"/><path class="a3uie0bxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:triangle-alert" /></template>
