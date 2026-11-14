<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/pxy4pkb4g.css';
import '../../css/h/hszogpsne.css';
import '../../css/a/a5706cu5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="pxy4pkb4g"/><path class="hszogpsne"/><path class="a5706cu5c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:message-secure-01" /></template>
