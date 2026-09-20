<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i__b08bke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i__b08bke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:rasa" /></template>
