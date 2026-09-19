<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ratr-0b0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":974,"height":1024};
const content = `<path class="ratr-0b0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:whmcs" /></template>
