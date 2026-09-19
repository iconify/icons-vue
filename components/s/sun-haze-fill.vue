<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa2e7s9da.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="aa2e7s9da"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:sun-haze-fill" /></template>
