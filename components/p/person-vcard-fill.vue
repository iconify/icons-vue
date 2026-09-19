<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqq74hb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vqq74hb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:person-vcard-fill" /></template>
