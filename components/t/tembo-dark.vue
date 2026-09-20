<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd5_iibfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":153,"height":152};
const content = `<path clip-rule="evenodd" class="fd5_iibfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tembo-dark" /></template>
