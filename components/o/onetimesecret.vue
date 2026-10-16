<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v22tdl34m.css';
import '../../css/x/xn2g6_jxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="v22tdl34m"/><path class="xn2g6_jxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:onetimesecret" /></template>
