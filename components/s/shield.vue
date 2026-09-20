<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubzmrab9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubzmrab9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:shield" /></template>
