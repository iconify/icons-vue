<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr5fyxn9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="fr5fyxn9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:video-alt" /></template>
