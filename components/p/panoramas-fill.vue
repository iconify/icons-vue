<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/redrvbb7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="redrvbb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:panoramas-fill" /></template>
