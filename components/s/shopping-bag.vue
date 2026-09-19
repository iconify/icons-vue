<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2cephbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2cephbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:shopping-bag" /></template>
