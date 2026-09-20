<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/beckg56qa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="beckg56qa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:transit-connection" /></template>
