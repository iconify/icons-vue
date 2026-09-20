<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb2e_5bwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb2e_5bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:minimize-2" /></template>
