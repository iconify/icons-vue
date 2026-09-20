<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1md_z23q.css';
import '../../css/l/lo6resb1g.css';
import '../../css/n/nncz9ebus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t1md_z23q"/><path class="lo6resb1g"/><path class="nncz9ebus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nyt-wordle" /></template>
