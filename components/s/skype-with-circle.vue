<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4cqdcc1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e4cqdcc1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:skype-with-circle" /></template>
