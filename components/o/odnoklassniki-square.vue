<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwj_zibxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="nwj_zibxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:odnoklassniki-square" /></template>
