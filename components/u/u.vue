<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huqq55bvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="huqq55bvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:u" /></template>
