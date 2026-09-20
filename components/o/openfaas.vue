<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi-4w3bku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fi-4w3bku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:openfaas" /></template>
