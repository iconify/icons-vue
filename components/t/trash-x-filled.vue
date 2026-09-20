<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0vmu_bgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0vmu_bgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:trash-x-filled" /></template>
