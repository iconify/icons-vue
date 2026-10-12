<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3m8f8bnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y3m8f8bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-asterisk-filled" /></template>
