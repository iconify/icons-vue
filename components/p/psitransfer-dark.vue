<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt1s5mb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dt1s5mb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:psitransfer-dark" /></template>
