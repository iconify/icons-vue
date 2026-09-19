<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/miqof0biz.css';
import '../../css/p/p-rfurwvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":12};
const content = `<path class="miqof0biz"/><path class="p-rfurwvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:rewind" /></template>
