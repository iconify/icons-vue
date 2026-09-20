<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-ed46g8a.css';
import '../../css/l/l7xst3nbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="g-ed46g8a"/><path class="l7xst3nbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:u-s-bank" /></template>
