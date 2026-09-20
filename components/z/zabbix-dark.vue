<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecdu1dgna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ecdu1dgna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zabbix-dark" /></template>
