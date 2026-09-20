<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm_ynkx1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zm_ynkx1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:sign-in-alt" /></template>
