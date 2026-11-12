<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9t074brf.css';
import '../../css/o/o_5jqwb6l.css';
import '../../css/s/s8uw1xbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l9t074brf"/><path class="o_5jqwb6l"/><circle class="s8uw1xbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:world-monitor-dark" /></template>
