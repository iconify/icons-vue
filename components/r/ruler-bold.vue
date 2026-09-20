<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhwig8hxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhwig8hxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ruler-bold" /></template>
