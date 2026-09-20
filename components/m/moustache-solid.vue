<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4patjbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s4patjbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:moustache-solid" /></template>
