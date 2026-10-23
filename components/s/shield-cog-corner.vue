<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uc1vmxbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uc1vmxbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:shield-cog-corner" /></template>
