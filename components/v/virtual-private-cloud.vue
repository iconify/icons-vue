<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8a0o-eya.css';
import '../../css/b/bde2b1vcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y8a0o-eya"/><path class="bde2b1vcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:virtual-private-cloud" /></template>
