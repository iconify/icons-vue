<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyw2t8n3g.css';
import '../../css/f/fqmfpk6cs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qyw2t8n3g"/><path class="fqmfpk6cs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:refresh" /></template>
