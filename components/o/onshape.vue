<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vigb5_xuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":220,"height":62};
const content = `<path class="vigb5_xuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:onshape" /></template>
