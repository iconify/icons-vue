<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okle9ebwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okle9ebwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:man" /></template>
