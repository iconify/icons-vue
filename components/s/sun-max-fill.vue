<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pzzrj50-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="pzzrj50-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:sun-max-fill" /></template>
