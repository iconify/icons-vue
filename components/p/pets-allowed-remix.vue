<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z06ct1bdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z06ct1bdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pets-allowed-remix" /></template>
