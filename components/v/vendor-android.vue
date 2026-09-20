<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_8oy0b2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_8oy0b2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:vendor-android" /></template>
