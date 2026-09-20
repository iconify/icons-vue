<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f25raz9at.css';
import '../../css/h/h67twkbcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path clip-rule="evenodd" class="f25raz9at"/><path class="h67twkbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:share-1-circle" /></template>
