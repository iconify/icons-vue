<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6u949tnp.css';
import '../../css/u/uxjv9458g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w6u949tnp"/><path class="uxjv9458g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yarr" /></template>
