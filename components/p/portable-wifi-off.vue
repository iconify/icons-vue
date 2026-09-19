<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjf1anbpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":424};
const content = `<path class="kjf1anbpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:portable-wifi-off" /></template>
