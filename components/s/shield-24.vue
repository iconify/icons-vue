<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7y0q8bps.css';
import '../../css/d/d25y6j89z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7y0q8bps"/><path class="d25y6j89z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:shield-24" /></template>
