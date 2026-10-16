<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh4vbpr-i.css';
import '../../css/d/dq961ejjd.css';
import '../../css/t/tdesojbkc.css';
import '../../css/n/ngtmo646m.css';
import '../../css/p/phh1iozuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mh4vbpr-i"/><path class="dq961ejjd"/><path class="tdesojbkc"/><path class="ngtmo646m"/><path class="phh1iozuu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:water-pump-20" /></template>
