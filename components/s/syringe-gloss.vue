<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq6od-5yc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bq6od-5yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:syringe-gloss" /></template>
