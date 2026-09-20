<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpttwux-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpttwux-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:umbrella-filled" /></template>
