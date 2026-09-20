<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkrm66bda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkrm66bda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:topology-ring-2" /></template>
