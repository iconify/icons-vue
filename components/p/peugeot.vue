<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5zis5bkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5zis5bkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:peugeot" /></template>
