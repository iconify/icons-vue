<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odavwabhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odavwabhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:zoom-outline" /></template>
