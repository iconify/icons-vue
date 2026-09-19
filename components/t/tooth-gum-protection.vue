<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u59jxfb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u59jxfb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:tooth-gum-protection" /></template>
