<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-l1cry_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-l1cry_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:menu-left" /></template>
