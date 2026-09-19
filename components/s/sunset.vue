<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o91sm0_iw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="o91sm0_iw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:sunset" /></template>
