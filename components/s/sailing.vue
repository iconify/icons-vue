<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nom8aq2sg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="nom8aq2sg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:sailing" /></template>
