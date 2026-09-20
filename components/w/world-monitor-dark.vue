<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9t074brf.css';
import '../../css/v/v-7b52b6r.css';
import '../../css/x/xmmjaib5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l9t074brf"/><path class="v-7b52b6r"/><circle class="xmmjaib5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:world-monitor-dark" /></template>
