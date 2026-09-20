<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifod5ubje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifod5ubje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:repeat-once" /></template>
