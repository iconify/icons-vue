<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6116jr8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6116jr8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:shield-checkered" /></template>
