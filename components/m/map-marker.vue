<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e65_xe.css';
import '../../css/l/lb41ec.css';
import '../../css/s/so-from-48.css';
import '../../css/r/r-to-0px.css';
import '../../css/r/r-to-2_5px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e65_xe"/><circle class="lb41ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:map-marker" /></template>
