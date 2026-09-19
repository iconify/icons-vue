<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svm6yqi6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="svm6yqi6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:share-outline" /></template>
