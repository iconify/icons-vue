<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1ch9w2el.css';
import '../../css/n/n4n5f992h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w1ch9w2el"/><path class="n4n5f992h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:settings-edit" /></template>
