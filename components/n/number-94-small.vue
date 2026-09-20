<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyjk4jbti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyjk4jbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:number-94-small" /></template>
