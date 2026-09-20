<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc0o0xwir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oc0o0xwir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mi:repeat" /></template>
