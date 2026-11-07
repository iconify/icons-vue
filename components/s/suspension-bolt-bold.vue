<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r34ssebvg.css';
import '../../css/k/kroiddczm.css';
import '../../css/m/mmoj81bwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r34ssebvg"/><path class="kroiddczm"/><path class="mmoj81bwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:suspension-bolt-bold" /></template>
