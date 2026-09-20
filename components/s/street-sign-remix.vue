<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhf9831qg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nhf9831qg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:street-sign-remix" /></template>
