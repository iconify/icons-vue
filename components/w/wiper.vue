<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvfhzyx9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvfhzyx9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:wiper" /></template>
