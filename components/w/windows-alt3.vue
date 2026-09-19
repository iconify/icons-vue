<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgw40dbso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zgw40dbso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:windows-alt3" /></template>
