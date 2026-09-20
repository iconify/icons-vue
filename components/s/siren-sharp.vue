<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddo040ffb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddo040ffb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:siren-sharp" /></template>
