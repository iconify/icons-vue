<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyo1nlb1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dyo1nlb1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:tshirt-outline" /></template>
