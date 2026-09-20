<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phr1lacdp.css';
import '../../css/c/cvbt36bli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="phr1lacdp"/><path clip-rule="evenodd" class="cvbt36bli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:photo-camera-32" /></template>
