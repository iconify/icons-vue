<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjnxpnb1o.css';
import '../../css/m/mr3oerbqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xjnxpnb1o"/><path class="mr3oerbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:offshore-substation-20" /></template>
