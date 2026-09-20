<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mg2h2obyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mg2h2obyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:thangs" /></template>
