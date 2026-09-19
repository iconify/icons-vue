<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-xu_c3ui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="u-xu_c3ui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:sad-cry" /></template>
