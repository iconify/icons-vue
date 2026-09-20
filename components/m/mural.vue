<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/istr8abqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="istr8abqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mural" /></template>
