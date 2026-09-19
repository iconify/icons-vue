<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjyn87vet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wjyn87vet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:male" /></template>
