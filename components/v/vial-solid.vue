<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_xux5b4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b_xux5b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:vial-solid" /></template>
