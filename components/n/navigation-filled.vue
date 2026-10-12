<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw8_nh79g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kw8_nh79g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:navigation-filled" /></template>
