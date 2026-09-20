<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmd7ifbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmd7ifbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:sort-number-desc" /></template>
