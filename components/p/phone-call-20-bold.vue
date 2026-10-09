<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jozh0c8mh.css';
import '../../css/w/wred-9hyr.css';
import '../../css/o/o8obgx-hp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jozh0c8mh"/><path class="wred-9hyr"/><path class="o8obgx-hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:phone-call-20-bold" /></template>
