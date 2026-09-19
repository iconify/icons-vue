<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eykbg7b3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="eykbg7b3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:prestashop" /></template>
