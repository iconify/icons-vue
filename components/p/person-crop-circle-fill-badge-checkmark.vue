<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cosm17b9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="cosm17b9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:person-crop-circle-fill-badge-checkmark" /></template>
