<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8qladuvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8qladuvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wheelchair-round" /></template>
