<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1x937zvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c1x937zvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ribbon-outline-24px" /></template>
