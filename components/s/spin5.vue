<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o27adk0py.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="o27adk0py"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontelico:spin5" /></template>
