<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sniv8rcns.css';
import '../../css/o/oss8yqu8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="sniv8rcns"/><circle class="oss8yqu8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:uptimerobot-light" /></template>
