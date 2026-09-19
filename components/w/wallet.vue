<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/mcopcxbjz.css';
import '../../css/f/f4-st3beb.css';
import '../../css/v/veijp88xp.css';
import '../../css/y/ye7rq2zrl.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGMTklgqzt"><g class="s9cl3zbei"><path clip-rule="evenodd" class="mcopcxbjz"/><path class="f4-st3beb"/><path class="veijp88xp"/><path class="ye7rq2zrl"/></g></mask></defs><path mask="url(#SVGMTklgqzt)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:wallet" /></template>
