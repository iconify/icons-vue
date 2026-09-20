<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af2k9-byt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="af2k9-byt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:openlayers" /></template>
