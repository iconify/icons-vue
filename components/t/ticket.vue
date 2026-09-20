<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7354sb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7354sb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ticket" /></template>
