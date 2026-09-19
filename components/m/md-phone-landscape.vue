<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uduft6fay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uduft6fay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-phone-landscape" /></template>
