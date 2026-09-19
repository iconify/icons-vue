<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxvvs3bmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxvvs3bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:skip-backward" /></template>
