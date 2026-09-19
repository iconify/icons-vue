<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa3ux0u-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":437,"height":512};
const content = `<path class="aa3ux0u-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:raml" /></template>
