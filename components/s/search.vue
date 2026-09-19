<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_atz4b9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a_atz4b9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:search" /></template>
