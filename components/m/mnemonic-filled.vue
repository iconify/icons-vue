<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_mfqsxhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r_mfqsxhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:mnemonic-filled" /></template>
