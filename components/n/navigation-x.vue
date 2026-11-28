<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msr1rpbkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msr1rpbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:navigation-x" /></template>
