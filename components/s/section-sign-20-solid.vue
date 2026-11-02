<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_ej9heil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="v_ej9heil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:section-sign-20-solid" /></template>
