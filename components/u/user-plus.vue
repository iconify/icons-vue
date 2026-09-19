<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-_7hlbrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-_7hlbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:user-plus" /></template>
