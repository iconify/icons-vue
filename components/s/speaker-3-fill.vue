<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iawiiv2tu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="iawiiv2tu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:speaker-3-fill" /></template>
