<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka0k06blu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ka0k06blu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:speakers" /></template>
