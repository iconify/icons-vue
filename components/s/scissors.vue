<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h02y9dblq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1408};
const content = `<path class="h02y9dblq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:scissors" /></template>
