<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8mz3qsho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i8mz3qsho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:pets-allowed-flat" /></template>
