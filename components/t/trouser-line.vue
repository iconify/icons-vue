<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/an9moxdyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="an9moxdyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:trouser-line" /></template>
