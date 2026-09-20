<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/deguiybxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="deguiybxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:warehouse-1-remix" /></template>
