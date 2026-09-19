<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgwi26b-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgwi26b-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:options-outline" /></template>
