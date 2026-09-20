<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aogk6ik8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aogk6ik8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:purgecss" /></template>
