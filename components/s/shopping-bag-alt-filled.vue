<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfs57crqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfs57crqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shopping-bag-alt-filled" /></template>
