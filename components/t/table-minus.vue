<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvs5w2btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvs5w2btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:table-minus" /></template>
