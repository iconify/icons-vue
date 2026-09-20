<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibcf01c0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibcf01c0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:repo-template-24" /></template>
