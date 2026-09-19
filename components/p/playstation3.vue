<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it8p9ubjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="it8p9ubjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:playstation3" /></template>
