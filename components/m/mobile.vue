<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il2q9bcjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="il2q9bcjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:mobile" /></template>
