<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eiqvwlcfe.css';
import '../../css/v/v11i6u_5o.css';
import '../../css/t/ty83n9sfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="eiqvwlcfe"/><path class="v11i6u_5o"/><path class="ty83n9sfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:record-player-20-bold" /></template>
