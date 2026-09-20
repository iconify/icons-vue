<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gx78nlbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gx78nlbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:pin-solid" /></template>
