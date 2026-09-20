<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz9atvzrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cz9atvzrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:plug-outline" /></template>
