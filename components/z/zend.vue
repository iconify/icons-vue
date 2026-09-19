<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfp75_bwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="zfp75_bwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:zend" /></template>
