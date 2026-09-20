<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1p4edmlk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1p4edmlk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wallet-sharp" /></template>
