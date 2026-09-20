<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr2arq_kw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tr2arq_kw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:trash2" /></template>
