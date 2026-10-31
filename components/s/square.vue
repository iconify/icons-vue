<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk07jkmaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tk07jkmaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:square" /></template>
