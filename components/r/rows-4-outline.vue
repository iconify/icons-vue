<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr6o49biw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fr6o49biw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rows-4-outline" /></template>
