<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2a6qzlrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r2a6qzlrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:notifications-alt-fill" /></template>
