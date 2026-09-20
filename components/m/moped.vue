<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awohm1b4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awohm1b4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:moped" /></template>
