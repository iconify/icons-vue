<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw_njbb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hw_njbb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:shield-x-mark" /></template>
