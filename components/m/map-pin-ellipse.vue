<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcg9_wbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="bcg9_wbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:map-pin-ellipse" /></template>
