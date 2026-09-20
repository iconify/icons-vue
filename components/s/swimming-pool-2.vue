<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mab8s_msf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mab8s_msf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:swimming-pool-2" /></template>
