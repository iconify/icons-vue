<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8v29kb-y.css';
import '../../css/n/n0l6v6lws.css';
import '../../css/w/wizgh3bae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="o8v29kb-y"/><path class="n0l6v6lws"/><path class="wizgh3bae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:spooty" /></template>
