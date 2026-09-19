<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu7w1mhzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="gu7w1mhzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:opencart" /></template>
