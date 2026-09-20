<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4as1zbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x4as1zbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:user-circle-single-solid" /></template>
