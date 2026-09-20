<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbdjjj2ra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbdjjj2ra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:social-facebook" /></template>
