<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzdld6fdb.css';
import '../../css/a/a1kinh57h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gzdld6fdb"/><circle class="a1kinh57h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:vlan-ibm" /></template>
