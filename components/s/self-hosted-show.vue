<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pixd3le1c.css';
import '../../css/n/nspe8_bkd.css';
import '../../css/r/r-0tybctz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="pixd3le1c"/><path class="nspe8_bkd"/><path class="r-0tybctz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:self-hosted-show" /></template>
