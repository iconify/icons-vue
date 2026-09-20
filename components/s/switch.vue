<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3-k29i5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3-k29i5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:switch" /></template>
