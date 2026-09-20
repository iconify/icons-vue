<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuuxkorgd.css';
import '../../css/m/m61dewcpl.css';
import '../../css/w/wz4e5ub6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yuuxkorgd"/><path class="m61dewcpl"/><path class="wz4e5ub6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:owntone" /></template>
