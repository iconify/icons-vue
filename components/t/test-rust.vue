<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbttgjpdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dbttgjpdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:test-rust" /></template>
