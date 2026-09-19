<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h93bu-h8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h93bu-h8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:more-or-less" /></template>
