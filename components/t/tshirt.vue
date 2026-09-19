<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_0vobhrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="m_0vobhrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:tshirt" /></template>
