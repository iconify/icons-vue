<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahhv7fb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1130,"height":178};
const content = `<path class="ahhv7fb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mercadona" /></template>
