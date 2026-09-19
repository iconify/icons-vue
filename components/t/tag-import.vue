<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca0if03mm.css';
import '../../css/u/uu_7gibiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ca0if03mm"/><path class="uu_7gibiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:tag-import" /></template>
