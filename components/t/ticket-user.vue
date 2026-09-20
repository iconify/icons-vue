<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au22jrneh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="au22jrneh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ticket-user" /></template>
