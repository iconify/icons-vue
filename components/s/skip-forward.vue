<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v27uo2wcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v27uo2wcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:skip-forward" /></template>
