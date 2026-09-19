<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn9q4acno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":788,"height":665};
const content = `<path class="sn9q4acno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:share" /></template>
