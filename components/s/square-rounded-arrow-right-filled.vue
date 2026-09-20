<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf5piqbyl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wf5piqbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:square-rounded-arrow-right-filled" /></template>
