<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la6dvw7cw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="la6dvw7cw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:refrigerator" /></template>
