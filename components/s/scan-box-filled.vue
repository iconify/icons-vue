<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k51rg04ze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k51rg04ze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:scan-box-filled" /></template>
