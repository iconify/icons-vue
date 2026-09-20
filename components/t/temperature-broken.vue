<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/nl9qzn-xd.css';
import '../../css/y/yzw658yku.css';
import '../../css/w/w2iuc4byh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nl9qzn-xd"/><path class="yzw658yku"/><path class="w2iuc4byh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:temperature-broken" /></template>
