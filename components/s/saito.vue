<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6o7oeb6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6o7oeb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:saito" /></template>
