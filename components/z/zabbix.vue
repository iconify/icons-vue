<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrn8gobul.css';
import '../../css/d/dp_5ikbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="wrn8gobul"/><path class="dp_5ikbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:zabbix" /></template>
