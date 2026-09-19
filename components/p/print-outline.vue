<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxrn8tbcm.css';
import '../../css/x/xue14cb9o.css';
import '../../css/u/u1b3xzbod.css';
import '../../css/d/dbogasj6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wxrn8tbcm"/><rect class="xue14cb9o"/><path class="u1b3xzbod"/><circle class="dbogasj6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:print-outline" /></template>
