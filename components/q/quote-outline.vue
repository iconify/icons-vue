<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ii1_3rbrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ii1_3rbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:quote-outline" /></template>
