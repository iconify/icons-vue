<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftehj-c2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ftehj-c2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:sigma" /></template>
