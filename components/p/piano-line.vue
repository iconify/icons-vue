<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr0kq8bko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fr0kq8bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:piano-line" /></template>
