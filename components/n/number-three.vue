<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da_3gqzme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da_3gqzme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:number-three" /></template>
