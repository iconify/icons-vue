<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz0vojboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kz0vojboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-top-open-sharp" /></template>
