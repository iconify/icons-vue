<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b34h2hbbd.css';
import '../../css/m/mgf3uccoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":16};
const content = `<path class="b34h2hbbd"/><path class="mgf3uccoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:share" /></template>
