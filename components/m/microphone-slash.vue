<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofy-cuz9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofy-cuz9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:microphone-slash" /></template>
