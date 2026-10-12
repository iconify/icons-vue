<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjvc8yb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pjvc8yb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:trailer-filled" /></template>
