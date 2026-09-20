<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtu-8o8di.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtu-8o8di"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:suckless" /></template>
