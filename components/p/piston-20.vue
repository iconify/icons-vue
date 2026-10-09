<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjnxpnb1o.css';
import '../../css/d/dk6kerbsg.css';
import '../../css/b/be65o352o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xjnxpnb1o"/><path class="dk6kerbsg"/><path class="be65o352o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:piston-20" /></template>
