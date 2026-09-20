<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-djw4b1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-djw4b1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:phone-incoming" /></template>
