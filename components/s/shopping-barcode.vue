<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9-sgc7ks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":35,"height":24};
const content = `<path class="m9-sgc7ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:shopping-barcode" /></template>
