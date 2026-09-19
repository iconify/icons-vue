<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlvjibc5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tlvjibc5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:whatsapp-fill-16" /></template>
