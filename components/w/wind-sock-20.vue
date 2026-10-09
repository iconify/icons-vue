<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp3sh4q-z.css';
import '../../css/c/co-d1_b7k.css';
import '../../css/t/tbph25zil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vp3sh4q-z"/><path class="co-d1_b7k"/><path class="tbph25zil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-sock-20" /></template>
