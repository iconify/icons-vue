<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctu-0cbpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctu-0cbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:square-divide" /></template>
