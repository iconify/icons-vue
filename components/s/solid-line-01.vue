<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhc5occtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhc5occtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:solid-line-01" /></template>
