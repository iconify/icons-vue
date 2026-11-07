<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/nl9qzn-xd.css';
import '../../css/k/ktz4j74-r.css';
import '../../css/w/w0kh5pr9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nl9qzn-xd"/><path class="ktz4j74-r"/><path class="w0kh5pr9u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:temperature-broken" /></template>
