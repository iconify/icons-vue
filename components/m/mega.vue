<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fug_uwbpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="fug_uwbpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:mega" /></template>
