<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2-y9fm_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u2-y9fm_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-letter-c-filled" /></template>
