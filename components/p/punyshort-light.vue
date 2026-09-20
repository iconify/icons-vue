<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc6r_1jfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jc6r_1jfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:punyshort-light" /></template>
