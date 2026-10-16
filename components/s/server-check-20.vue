<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5j847bee.css';
import '../../css/p/pr4dqmbxn.css';
import '../../css/q/qh3-d7bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w5j847bee"/><path class="pr4dqmbxn"/><path class="qh3-d7bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:server-check-20" /></template>
