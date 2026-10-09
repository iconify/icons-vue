<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwd41ubru.css';
import '../../css/r/rp4u3sbxm.css';
import '../../css/g/gfzae_buv.css';
import '../../css/z/zery2jbhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dwd41ubru"/><path class="rp4u3sbxm"/><path class="gfzae_buv"/><path class="zery2jbhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:qr-code-20-bold" /></template>
