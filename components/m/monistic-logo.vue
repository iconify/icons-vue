<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b52cj7bic.css';
import '../../css/d/de917sbiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="b52cj7bic"/><path class="de917sbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:monistic-logo" /></template>
