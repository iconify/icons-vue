<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eeo0agb5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eeo0agb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:square-arrows-right-filled" /></template>
