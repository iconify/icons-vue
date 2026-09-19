<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuoe7pgag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="vuoe7pgag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontelico:spin1" /></template>
