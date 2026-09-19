<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jaze2cbns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jaze2cbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tooth-extraction-filled" /></template>
