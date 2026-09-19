<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozoj0vbaf.css';
import '../../css/k/khkqlacip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozoj0vbaf"/><path class="khkqlacip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:swimming-filled" /></template>
