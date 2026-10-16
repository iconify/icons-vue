<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3sh15b-h.css';
import '../../css/m/mwwltnb7y.css';
import '../../css/f/fuabohb_q.css';
import '../../css/n/n2rzbnimr.css';
import '../../css/k/kvl9ucc0s.css';
import '../../css/n/n0oj8po7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n3sh15b-h"/><path class="mwwltnb7y"/><path class="fuabohb_q"/><path class="n2rzbnimr"/><path class="kvl9ucc0s"/><path class="n0oj8po7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:weather-station-20" /></template>
