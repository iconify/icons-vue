<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvyetjk1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":25};
const content = `<path clip-rule="evenodd" class="vvyetjk1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:share-1" /></template>
