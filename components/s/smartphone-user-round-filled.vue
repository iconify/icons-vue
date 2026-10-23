<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/piwsv7bod.css';
import '../../css/c/c5at6trmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="piwsv7bod"/><path class="c5at6trmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:smartphone-user-round-filled" /></template>
