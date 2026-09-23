<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i52wc5bqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":33,"height":33};
const content = `<path clip-rule="evenodd" class="i52wc5bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:okta" /></template>
