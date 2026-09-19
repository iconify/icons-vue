<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irl9z8uwq.css';
import '../../css/i/ioz8g2bzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="irl9z8uwq"/><path class="ioz8g2bzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:social-html5-outline" /></template>
