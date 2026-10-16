<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/supgx2bpn.css';
import '../../css/s/ss4fa8bou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="supgx2bpn"/><path class="ss4fa8bou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pipe-tee-20" /></template>
