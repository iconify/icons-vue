<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t871fxb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t871fxb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:ocaml" /></template>
