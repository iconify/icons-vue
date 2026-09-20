<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1l3lq7gm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1l3lq7gm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:microsoft-xbox-controller-view" /></template>
