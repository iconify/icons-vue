<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkh8abbvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="tkh8abbvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:tray-headset-26" /></template>
