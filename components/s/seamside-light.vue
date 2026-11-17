<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgk61_5ts.css';
import '../../css/i/i4y13ubio.css';
import '../../css/n/n-f605bde.css';
import '../../css/w/wzmyd8b0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xgk61_5ts"/><path class="i4y13ubio"/><path class="n-f605bde"/><path class="wzmyd8b0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:seamside-light" /></template>
