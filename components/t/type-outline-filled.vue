<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwrs5jbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwrs5jbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:type-outline-filled" /></template>
