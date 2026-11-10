<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg33pwb_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sg33pwb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:trash-arrow-up-solid" /></template>
