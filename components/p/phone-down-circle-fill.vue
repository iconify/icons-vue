<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz55hfrey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="pz55hfrey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:phone-down-circle-fill" /></template>
