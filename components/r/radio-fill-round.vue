<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh9n6fbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nh9n6fbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:radio-fill-round" /></template>
