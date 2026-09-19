<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyzz-jbto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xyzz-jbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ppe-mask-24px" /></template>
