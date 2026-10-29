<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/m/m1t32eo2u.css';
import '../../css/p/pdldxnb-u.css';
import '../../css/n/nfyqixscy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="m1t32eo2u"/><path class="pdldxnb-u wm-a"/><path class="nfyqixscy wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:spider-solid" /></template>
