<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bfhcyi7lp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bfhcyi7lp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:stamp-filled" /></template>
