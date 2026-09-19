<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7s6tsbkb.css';
import '../../css/n/n-u2bhuwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7s6tsbkb"/><path class="n-u2bhuwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:minus-square-outline" /></template>
