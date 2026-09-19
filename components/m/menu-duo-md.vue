<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsgw3bbqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsgw3bbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:menu-duo-md" /></template>
