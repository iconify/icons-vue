<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoon22kar.css';
import '../../css/m/m-kckroos.css';
import '../../css/q/q1lth85bf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="eoon22kar"/><path class="m-kckroos"/><path class="q1lth85bf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-pump-20" /></template>
