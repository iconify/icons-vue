<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spds58vva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spds58vva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:moon" /></template>
