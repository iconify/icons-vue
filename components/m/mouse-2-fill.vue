<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td859mbpm.css';
import '../../css/p/pmiyxhb-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td859mbpm"/><path class="pmiyxhb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:mouse-2-fill" /></template>
