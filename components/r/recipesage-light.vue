<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0o80mktc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m0o80mktc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:recipesage-light" /></template>
