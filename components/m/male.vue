<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po02nqb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":303,"height":720};
const content = `<path class="po02nqb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:male" /></template>
