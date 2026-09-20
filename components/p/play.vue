<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3124ccsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="a3124ccsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:play" /></template>
