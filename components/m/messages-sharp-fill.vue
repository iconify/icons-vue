<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htv5wib5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htv5wib5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:messages-sharp-fill" /></template>
