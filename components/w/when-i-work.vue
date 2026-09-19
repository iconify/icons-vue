<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkb3nuooz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vkb3nuooz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:when-i-work" /></template>
