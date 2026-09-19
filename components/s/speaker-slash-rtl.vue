<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt5xb2bco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="qt5xb2bco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:speaker-slash-rtl" /></template>
