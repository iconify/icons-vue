<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sws6u3btr.css';
import '../../css/b/blhityb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sws6u3btr"/><path class="blhityb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:s-alt" /></template>
