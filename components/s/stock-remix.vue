<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr-9dwl7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fr-9dwl7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:stock-remix" /></template>
