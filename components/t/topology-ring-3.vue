<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vjub1141u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjub1141u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:topology-ring-3" /></template>
