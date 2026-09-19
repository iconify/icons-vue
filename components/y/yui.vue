<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxxf_6bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":960};
const content = `<path class="rxxf_6bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:yui" /></template>
