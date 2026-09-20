<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz9uk5bnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz9uk5bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:play-card-7-filled" /></template>
