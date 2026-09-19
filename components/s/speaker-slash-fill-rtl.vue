<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mm_ngjbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="mm_ngjbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:speaker-slash-fill-rtl" /></template>
