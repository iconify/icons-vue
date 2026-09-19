<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axi7sujok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="axi7sujok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:plaster-filled" /></template>
