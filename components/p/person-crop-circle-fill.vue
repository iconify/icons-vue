<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue493ubff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ue493ubff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:person-crop-circle-fill" /></template>
