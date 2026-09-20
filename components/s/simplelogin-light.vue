<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyucu1t5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uyucu1t5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:simplelogin-light" /></template>
