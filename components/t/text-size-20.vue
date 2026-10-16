<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9f_3wnku.css';
import '../../css/n/n-pf8dtms.css';
import '../../css/t/tn_egrb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e9f_3wnku"/><path class="n-pf8dtms"/><path class="tn_egrb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:text-size-20" /></template>
