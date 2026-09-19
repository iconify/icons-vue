<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntlcj1e_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntlcj1e_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:map" /></template>
