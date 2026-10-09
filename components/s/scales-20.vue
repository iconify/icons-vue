<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s60tohl9o.css';
import '../../css/p/pzzjixb2k.css';
import '../../css/b/b_n-robbb.css';
import '../../css/w/wh3r_vb2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s60tohl9o"/><path class="pzzjixb2k"/><path class="b_n-robbb"/><path class="wh3r_vb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scales-20" /></template>
