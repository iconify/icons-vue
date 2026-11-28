<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw-2bgbkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary sw-2bgbkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:moon-duotone" /></template>
