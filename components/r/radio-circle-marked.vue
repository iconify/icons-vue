<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho624zber.css';
import '../../css/a/adot17bzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ho624zber"/><path class="adot17bzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:radio-circle-marked" /></template>
