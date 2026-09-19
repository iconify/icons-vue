<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvjgifbok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="dvjgifbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:mobile-phone-alt2-small" /></template>
