<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px1aoe-8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="px1aoe-8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:office-badge" /></template>
