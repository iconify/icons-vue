<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dp6r5wbyh.css';
import '../../css/g/gtr6zk6db.css';
import '../../css/d/dl_nt7bof.css';
import '../../css/y/ydacol75i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dp6r5wbyh"/><path class="gtr6zk6db"/><path class="dl_nt7bof"/><path class="ydacol75i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:motorcycle-48" /></template>
