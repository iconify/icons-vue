<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn3d9nbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kn3d9nbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:refresh-cancelled" /></template>
