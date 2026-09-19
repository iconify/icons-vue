<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l68n69bau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l68n69bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:wheelchair-2" /></template>
