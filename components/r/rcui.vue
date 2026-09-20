<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gbfficpwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1280,"height":1280};
const content = `<path class="gbfficpwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:rcui" /></template>
