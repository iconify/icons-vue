<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr6y515mv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fr6y515mv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:right-small-outline" /></template>
