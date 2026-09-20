<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ansc-jpyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ansc-jpyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:traffic-economy-bold" /></template>
