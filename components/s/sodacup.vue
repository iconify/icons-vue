<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjkki5lld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":1024};
const content = `<path class="gjkki5lld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:sodacup" /></template>
