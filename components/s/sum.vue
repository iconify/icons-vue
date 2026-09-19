<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pabg61oak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":1024};
const content = `<path class="pabg61oak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:sum" /></template>
