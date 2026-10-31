<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obdtc0bpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obdtc0bpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:repeat-duocolor-round" /></template>
