<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvwtus5-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvwtus5-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:poe" /></template>
