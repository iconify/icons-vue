<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmsnddboj.css';
import '../../css/j/jc8vjxbbg.css';
import '../../css/g/g68oh1czg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bmsnddboj"/><path class="jc8vjxbbg"/><path class="g68oh1czg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tea-cup-48" /></template>
