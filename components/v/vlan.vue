<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nym22vbim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nym22vbim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:vlan" /></template>
