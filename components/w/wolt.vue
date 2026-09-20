<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec_8xh-nb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":154,"height":56};
const content = `<path class="ec_8xh-nb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:wolt" /></template>
