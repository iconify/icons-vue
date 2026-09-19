<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jed186bsr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jed186bsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:satoshi-v3-filled" /></template>
