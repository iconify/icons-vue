<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x9n_irbva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="x9n_irbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-arrow-up" /></template>
