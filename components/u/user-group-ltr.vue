<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yoirqcbtc.css';
import '../../css/o/ojb5ey7sa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yoirqcbtc"/><circle class="ojb5ey7sa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:user-group-ltr" /></template>
