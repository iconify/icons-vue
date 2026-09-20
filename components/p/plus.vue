<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bttz41b-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bttz41b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:plus" /></template>
