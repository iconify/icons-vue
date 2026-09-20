<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy_j258tn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wy_j258tn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shield-minus" /></template>
