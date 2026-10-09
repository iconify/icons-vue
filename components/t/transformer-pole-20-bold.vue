<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qielwupdx.css';
import '../../css/x/x7x2mcb9a.css';
import '../../css/l/l7htvzbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qielwupdx"/><path class="x7x2mcb9a"/><path class="l7htvzbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:transformer-pole-20-bold" /></template>
