<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4mp-ib-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a4mp-ib-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-shine-outline" /></template>
