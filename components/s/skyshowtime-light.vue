<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp_59jbzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zp_59jbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:skyshowtime-light" /></template>
