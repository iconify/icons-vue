<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhq581brg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhq581brg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:meh-alt-filled" /></template>
