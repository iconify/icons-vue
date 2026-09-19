<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_ohfvbml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_ohfvbml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:txt-01" /></template>
