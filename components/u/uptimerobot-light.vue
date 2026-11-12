<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4rsj3bvm.css';
import '../../css/o/oss8yqu8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="q4rsj3bvm"/><circle class="oss8yqu8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:uptimerobot-light" /></template>
