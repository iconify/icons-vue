<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8nnbix4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8nnbix4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:zebpay" /></template>
