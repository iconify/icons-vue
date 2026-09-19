<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr2kdabse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="fr2kdabse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:right-black-triangle" /></template>
