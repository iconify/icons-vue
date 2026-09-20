<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc_dl32mw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc_dl32mw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mlflow" /></template>
