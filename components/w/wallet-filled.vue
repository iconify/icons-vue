<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qre9t1brz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qre9t1brz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:wallet-filled" /></template>
