<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znvomhwkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":304,"height":488};
const content = `<path class="znvomhwkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:tumblr" /></template>
