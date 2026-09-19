<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lda3vs_wa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":717,"height":698};
const content = `<path class="lda3vs_wa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:smile" /></template>
