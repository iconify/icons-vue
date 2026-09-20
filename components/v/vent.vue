<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwn4t2-5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwn4t2-5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:vent" /></template>
