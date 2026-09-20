<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuzlutbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wuzlutbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:nftart" /></template>
