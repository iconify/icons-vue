<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aikpq8biq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aikpq8biq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:note-with-text-fill" /></template>
