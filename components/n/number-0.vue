<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exbi6cc1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exbi6cc1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:number-0" /></template>
