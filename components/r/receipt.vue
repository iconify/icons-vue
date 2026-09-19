<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cajek1mxb.css';
import '../../css/y/yjjqxcmso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cajek1mxb"/><path class="yjjqxcmso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:receipt" /></template>
