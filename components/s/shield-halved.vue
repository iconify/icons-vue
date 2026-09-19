<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n83m5i-4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n83m5i-4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:shield-halved" /></template>
