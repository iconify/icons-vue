<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmrgqeb6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kmrgqeb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:roblox-dark" /></template>
