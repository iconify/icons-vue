<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u64em7bbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u64em7bbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:no-access-for-service-animal-3" /></template>
