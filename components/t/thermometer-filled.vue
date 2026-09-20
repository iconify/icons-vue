<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bzz-d2-zt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="bzz-d2-zt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:thermometer-filled" /></template>
