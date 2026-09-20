<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_1ean58s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c_1ean58s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-boarding" /></template>
