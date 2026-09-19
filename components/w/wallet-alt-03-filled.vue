<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9g9e5wbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c9g9e5wbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:wallet-alt-03-filled" /></template>
