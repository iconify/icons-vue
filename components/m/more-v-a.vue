<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee0hxn02z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":5,"height":24};
const content = `<path class="ee0hxn02z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:more-v-a" /></template>
