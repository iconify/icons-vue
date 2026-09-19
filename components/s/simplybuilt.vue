<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2ejlac0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n2ejlac0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:simplybuilt" /></template>
