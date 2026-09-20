<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0-i_vl6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n0-i_vl6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:satellite-bold" /></template>
