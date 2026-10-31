<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/crqpn7b-k.css';
import '../../css/c/c003gc-5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="crqpn7b-k"/><path class="c003gc-5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:unknown" /></template>
