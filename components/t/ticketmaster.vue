<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kieyk5oou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kieyk5oou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ticketmaster" /></template>
