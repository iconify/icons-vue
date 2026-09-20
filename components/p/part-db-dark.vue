<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de43k29rq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="de43k29rq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:part-db-dark" /></template>
