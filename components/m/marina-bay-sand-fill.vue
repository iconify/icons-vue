<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2pwz3vol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h2pwz3vol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:marina-bay-sand-fill" /></template>
