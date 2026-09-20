<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw_-m2kon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qw_-m2kon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:safari-logo-remix" /></template>
