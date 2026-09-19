<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lweg38u7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lweg38u7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:messages-outline" /></template>
