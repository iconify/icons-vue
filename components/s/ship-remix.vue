<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq5bz1lno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eq5bz1lno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:ship-remix" /></template>
