<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttw5pwbrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":666};
const content = `<path class="ttw5pwbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:shopping" /></template>
