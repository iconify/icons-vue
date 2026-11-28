<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwv2r1bnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwv2r1bnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:stairs-solid" /></template>
