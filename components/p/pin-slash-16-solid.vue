<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4gxisb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="f4gxisb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:pin-slash-16-solid" /></template>
