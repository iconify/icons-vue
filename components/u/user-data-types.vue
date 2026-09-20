<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu7iv3gez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nu7iv3gez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:user-data-types" /></template>
