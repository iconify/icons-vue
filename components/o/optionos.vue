<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eulpr3bjr.css';
import '../../css/r/rw8aspbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="eulpr3bjr"/><path class="rw8aspbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:optionos" /></template>
