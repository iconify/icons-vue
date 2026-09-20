<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu8djwm0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wu8djwm0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:medical-ribbon-1-remix" /></template>
