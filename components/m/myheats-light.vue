<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxzqot-ta.css';
import '../../css/s/szpwprb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hxzqot-ta"/><path class="szpwprb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:myheats-light" /></template>
