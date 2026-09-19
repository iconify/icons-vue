<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbv87hbui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lbv87hbui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:satellite" /></template>
