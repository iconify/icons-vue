<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er2a5vi2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="er2a5vi2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:trending-solid" /></template>
