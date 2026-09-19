<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncpn4wbbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ncpn4wbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:marko" /></template>
