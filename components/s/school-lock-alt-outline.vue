<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7r2ndbvq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7r2ndbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:school-lock-alt-outline" /></template>
