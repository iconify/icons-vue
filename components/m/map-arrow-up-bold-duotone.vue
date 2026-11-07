<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fevon8ayl.css';
import '../../css/z/z9t-ptwsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fevon8ayl"/><path class="z9t-ptwsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-arrow-up-bold-duotone" /></template>
