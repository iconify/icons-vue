<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh03lhbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uh03lhbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:shadow" /></template>
