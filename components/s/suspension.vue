<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s86v7ljxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s86v7ljxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:suspension" /></template>
