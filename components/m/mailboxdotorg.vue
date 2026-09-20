<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vied1fbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vied1fbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:mailboxdotorg" /></template>
