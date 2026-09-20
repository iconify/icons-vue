<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pha7npbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pha7npbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tamiya" /></template>
