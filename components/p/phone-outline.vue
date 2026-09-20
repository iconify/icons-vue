<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7z1bxusg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7z1bxusg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:phone-outline" /></template>
