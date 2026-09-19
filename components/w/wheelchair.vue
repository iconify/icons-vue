<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebz3snb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ebz3snb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:wheelchair" /></template>
