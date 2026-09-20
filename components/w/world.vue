<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzjdr7-si.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vzjdr7-si"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:world" /></template>
