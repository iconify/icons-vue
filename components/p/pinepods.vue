<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5wkahb5o.css';
import '../../css/i/ibdum26cr.css';
import '../../css/w/wc-vucb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="s5wkahb5o"/><path clip-rule="evenodd" class="ibdum26cr"/><path clip-rule="evenodd" class="wc-vucb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pinepods" /></template>
