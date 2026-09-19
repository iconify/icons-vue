<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifl6gthti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifl6gthti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:volume" /></template>
