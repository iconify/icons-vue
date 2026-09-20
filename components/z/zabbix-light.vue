<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kss7hkagu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kss7hkagu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zabbix-light" /></template>
