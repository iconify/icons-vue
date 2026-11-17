<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk9pgpbto.css';
import '../../css/i/ik-axzblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bk9pgpbto"/><path class="ik-axzblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-arrow-down-exit-filled" /></template>
