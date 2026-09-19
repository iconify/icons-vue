<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/har_mcb9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="har_mcb9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:slow-winds" /></template>
