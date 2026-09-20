<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lenqjybbl.css';
import '../../css/s/sizgdyb9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lenqjybbl"/><path class="sizgdyb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:smithery" /></template>
