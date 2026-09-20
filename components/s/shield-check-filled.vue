<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knz2nkbyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="knz2nkbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:shield-check-filled" /></template>
