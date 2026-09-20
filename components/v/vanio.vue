<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abwvd3b5g.css';
import '../../css/t/t7eub0bye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abwvd3b5g"/><path class="t7eub0bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vanio" /></template>
