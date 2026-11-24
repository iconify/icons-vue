<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlk96vv8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jlk96vv8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:plug-slash-solid" /></template>
