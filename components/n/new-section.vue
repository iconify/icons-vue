<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwr1d6buo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwr1d6buo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:new-section" /></template>
