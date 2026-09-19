<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_no1bbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b_no1bbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:phone-off-fill" /></template>
