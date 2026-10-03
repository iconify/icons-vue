<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qg60jfjeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qg60jfjeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:rakuten-viki-alt" /></template>
