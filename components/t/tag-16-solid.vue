<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9l4theml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y9l4theml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:tag-16-solid" /></template>
