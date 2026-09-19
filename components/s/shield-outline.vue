<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzp-x3bwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzp-x3bwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:shield-outline" /></template>
