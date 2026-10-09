<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tblmeeb4n.css';
import '../../css/o/o8vni54ea.css';
import '../../css/a/aiyg2ojqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tblmeeb4n"/><path class="o8vni54ea"/><path class="aiyg2ojqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:person-walking-20" /></template>
