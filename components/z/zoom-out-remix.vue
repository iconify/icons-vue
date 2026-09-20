<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwi6ptprm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zwi6ptprm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:zoom-out-remix" /></template>
