<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu4p30ims.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lu4p30ims"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:soft-drink-can-solid" /></template>
