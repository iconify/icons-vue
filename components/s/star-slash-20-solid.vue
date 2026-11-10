<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8cks3bvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m8cks3bvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:star-slash-20-solid" /></template>
