<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wszp3tskv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":24};
const content = `<path class="wszp3tskv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:mercury" /></template>
