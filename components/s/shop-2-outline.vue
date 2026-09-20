<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-_lkllye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s-_lkllye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shop-2-outline" /></template>
