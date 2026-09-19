<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-a1slwrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t-a1slwrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:store" /></template>
