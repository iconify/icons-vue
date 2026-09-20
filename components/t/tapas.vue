<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2b7qop6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2b7qop6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tapas" /></template>
