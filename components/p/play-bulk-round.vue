<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp6f-bgms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mp6f-bgms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:play-bulk-round" /></template>
