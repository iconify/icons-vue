<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-4xc8ofo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="f-4xc8ofo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:shield-lefthalf-fill" /></template>
