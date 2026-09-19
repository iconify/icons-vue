<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chhycz7fq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chhycz7fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:pantheon-filled" /></template>
