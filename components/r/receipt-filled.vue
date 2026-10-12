<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9eo20bcx.css';
import '../../css/b/bj3gvzbwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9eo20bcx"/><path clip-rule="evenodd" class="bj3gvzbwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:receipt-filled" /></template>
