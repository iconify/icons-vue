<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3-a3w-3w.css';
import '../../css/f/ff8-diyhm.css';
import '../../css/t/t2w8mls_d.css';
import '../../css/y/yl4w1c0xq.css';
import '../../css/s/skt64dbpg.css';
import '../../css/i/i3yihv7dd.css';
import '../../css/q/q9wzo3fbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="c3-a3w-3w"/><path class="ff8-diyhm"/><path class="t2w8mls_d"/><path class="yl4w1c0xq"/><path class="skt64dbpg"/><path class="i3yihv7dd"/><path class="q9wzo3fbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:mexico" /></template>
