<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-d5anb6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-d5anb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:no-touch" /></template>
