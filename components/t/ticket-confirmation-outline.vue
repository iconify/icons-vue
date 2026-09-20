<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hydikxbft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hydikxbft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ticket-confirmation-outline" /></template>
