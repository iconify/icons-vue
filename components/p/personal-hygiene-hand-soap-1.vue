<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks6--tb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ks6--tb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:personal-hygiene-hand-soap-1" /></template>
