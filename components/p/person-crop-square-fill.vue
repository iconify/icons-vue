<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eotl5ccee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="eotl5ccee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:person-crop-square-fill" /></template>
