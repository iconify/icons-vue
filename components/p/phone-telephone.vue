<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_jtldbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f_jtldbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:phone-telephone" /></template>
