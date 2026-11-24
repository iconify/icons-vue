<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5a1_3ush.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5a1_3ush"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:phone-pin" /></template>
