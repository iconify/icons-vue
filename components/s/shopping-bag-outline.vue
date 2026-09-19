<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sggzf-1qr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sggzf-1qr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:shopping-bag-outline" /></template>
