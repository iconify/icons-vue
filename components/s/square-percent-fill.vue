<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg8zehu1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bg8zehu1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-percent-fill" /></template>
