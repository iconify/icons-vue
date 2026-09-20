<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_3vfwbgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_3vfwbgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:sort-alt-duotone" /></template>
