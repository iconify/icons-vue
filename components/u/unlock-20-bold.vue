<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aq_b3258o.css';
import '../../css/h/his60jocq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="aq_b3258o"/><path class="his60jocq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:unlock-20-bold" /></template>
